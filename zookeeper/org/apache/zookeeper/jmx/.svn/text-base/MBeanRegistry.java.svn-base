/**
 * Licensed to the Apache Software Foundation (ASF) under one
 * or more contributor license agreements.  See the NOTICE file
 * distributed with this work for additional information
 * regarding copyright ownership.  The ASF licenses this file
 * to you under the Apache License, Version 2.0 (the
 * "License"); you may not use this file except in compliance
 * with the License.  You may obtain a copy of the License at
 *
 *     http://www.apache.org/licenses/LICENSE-2.0
 *
 * Unless required by applicable law or agreed to in writing, software
 * distributed under the License is distributed on an "AS IS" BASIS,
 * WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 * See the License for the specific language governing permissions and
 * limitations under the License.
 */

package org.apache.zookeeper.jmx;

import java.util.Map;
import java.util.concurrent.ConcurrentHashMap;

import org.slf4j.Logger;
import org.slf4j.LoggerFactory;

/**
 * This class provides a unified interface for registering/unregistering of zookeeper MBeans with the platform MBean server. It builds a hierarchy of MBeans where each MBean
 * represented by a filesystem-like path. Eventually, this hierarchy will be stored in the zookeeper data tree instance as a virtual data tree.
 */
public class MBeanRegistry
{
	private static final Logger LOG = LoggerFactory.getLogger(MBeanRegistry.class);

	private static MBeanRegistry instance = new MBeanRegistry();

	private Map<ZKMBeanInfo, String> mapBean2Path = new ConcurrentHashMap<ZKMBeanInfo, String>();

	private Map<String, ZKMBeanInfo> mapName2Bean = new ConcurrentHashMap<String, ZKMBeanInfo>();

	public static MBeanRegistry getInstance()
	{
		return instance;
	}

	public MBeanRegistry()
	{
	}

	/**
	 * Registers a new MBean with the platform MBean server.
	 * 
	 * @param bean
	 *            the bean being registered
	 * @param parent
	 *            if not null, the new bean will be registered as a child node of this parent.
	 */
	public void register(ZKMBeanInfo bean, ZKMBeanInfo parent)
	{
	}

	/**
	 * Unregister the MBean identified by the path.
	 * 
	 * @param path
	 * @param bean
	 */
	private void unregister(String path, ZKMBeanInfo bean)
	{
	}

	/**
	 * Unregister MBean.
	 * 
	 * @param bean
	 */
	public void unregister(ZKMBeanInfo bean)
	{
	}
}
