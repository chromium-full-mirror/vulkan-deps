# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'a57276bf558f5cf94d3a9854ebdf5a2236849a5a',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '6aba93196c86c82e8ebe50920876ae5c028acd9b',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '01e0577914a75a2569c846778c2f93aa8e6feddd',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '533a69c63ae773d90d03b206954ffffec6517dbd',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'a4f8ada9f4f97c45b8c89c57997be9cebaae65d2',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '35e5469b619bfeeaf30d8c8e54ddde20e8a9e5f5',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'fe4e68d30968c3128300986a31c8ef5242e090b1',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': 'a1e45945b3a84140956dc4672684090cf8e636a4',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '3b60aa235ce6695fb1d4118c5bf1122b394a6205',
}

deps = {
  'glslang/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/glslang@{glslang_revision}',
  },

  'lunarg-vulkantools/src': {
    'url': '{chromium_git}/external/github.com/LunarG/VulkanTools@{lunarg_vulkantools_revision}',
  },

  'spirv-cross/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Cross@{spirv_cross_revision}',
  },

  'spirv-headers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Headers@{spirv_headers_revision}',
  },

  'spirv-tools/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Tools@{spirv_tools_revision}',
  },

  'vulkan-headers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Headers@{vulkan_headers_revision}',
  },

  'vulkan-loader/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Loader@{vulkan_loader_revision}',
  },

  'vulkan-tools/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Tools@{vulkan_tools_revision}',
  },

  'vulkan-utility-libraries/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Utility-Libraries@{vulkan_utility_libraries_revision}',
  },

  'vulkan-validation-layers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-ValidationLayers@{vulkan_validation_revision}',
  },
}
